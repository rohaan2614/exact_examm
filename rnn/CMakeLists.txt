add_library(examm_nn generate_nn.cxx rnn_genome.cxx rnn.cxx lstm_node.cxx ugrnn_node.cxx delta_node.cxx gru_node.cxx enarc_node.cxx enas_dag_node.cxx random_dag_node.cxx mgu_node.cxx dnas_node.cxx mse.cxx rnn_node.cxx rnn_edge.cxx rnn_recurrent_edge.cxx rnn_node_interface.cxx genome_property.cxx)
target_link_libraries(examm_nn exact_time_series exact_weights exact_common)
