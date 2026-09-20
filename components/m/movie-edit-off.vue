<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc9vrfbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-edit-off" /></template>
<style>
.vc9vrfbaw {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.672.482-1.144Q3.963 5 4.634 5h.174l9.415 9.416l-2.377 2.376V19zm10.936-5.894L7.639 5h1.419l1.425 2.844l.156.156h2.919l-1.5-3h2.5l1.5 3h3l-1.5-3h1.826q.691 0 1.153.463T21 6.616v3.473q-.814-.274-1.616-.133q-.803.14-1.38.717zm4.639 1.91l.925-.956l-.925-.944l-.95.95zm-.639 1.873l-2.21-2.185l2.222-2.221q.148-.13.307-.19q.16-.062.32-.062q.165 0 .334.064q.17.064.298.193l.925.945q.129.148.19.308q.062.159.062.319t-.052.322t-.2.31zm1.821 4.677l-.713.713l-3.246-3.252l-.974.973h-2.21v-2.21l.974-.967L1.72 3.341l.714-.714z");
}

</style>
