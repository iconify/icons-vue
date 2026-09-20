<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o94w2abbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vacuum-2-outline-rounded" /></template>
<style>
.o94w2abbj {
  fill: currentColor;
  d: path("M12 11.808q-.31 0-.52-.22t-.21-.511q0-.31.21-.52t.52-.21q.29 0 .51.21t.22.52q0 .29-.22.51t-.51.22m-1.671 4.443l-1.812 1.812q.771.46 1.65.698q.88.24 1.833.24t1.833-.24q.879-.239 1.65-.699l-1.825-1.811zM12 5q-1.45 0-2.725.55T7.05 7.05t-1.5 2.225T5 12q0 1.69.724 3.108t1.959 2.367l1.958-1.958q-.858-.565-1.375-1.485q-.516-.92-.516-2.032q0-1.767 1.241-3.009T12 7.75t3.009 1.241Q16.25 10.233 16.25 12q0 1.112-.516 2.041q-.517.93-1.374 1.495l1.957 1.958q1.235-.95 1.959-2.377T19 12q0-1.45-.55-2.725t-1.5-2.225t-2.225-1.5T12 5m0 3.75q-1.365 0-2.308.952T8.75 12q0 1.366.942 2.308T12 15.25q1.346 0 2.298-.942T15.25 12q0-1.346-.952-2.298T12 8.75M12 20q-1.664 0-3.118-.626T6.34 17.66t-1.714-2.542T4 12t.626-3.118T6.34 6.34t2.542-1.714T12 4t3.118.626T17.66 6.34t1.714 2.542T20 12t-.626 3.118t-1.714 2.542t-2.542 1.714T12 20");
}

</style>
