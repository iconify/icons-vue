<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbsi1bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-outline-rounded" /></template>
<style>
.ilbsi1bcy {
  fill: currentColor;
  d: path("M10.73 4h2.54zm0 16h2.54zm0 1q-.341 0-.61-.205t-.372-.547l-.632-2.214q-.131-.423-.396-.81q-.264-.388-.707-.765q-.965-.809-1.489-1.965T6 12q0-1.313.524-2.47t1.49-1.99q.442-.402.706-.786q.264-.385.395-.788l.633-2.214q.104-.342.372-.547T10.73 3h2.54q.342 0 .61.205t.372.547l.633 2.214q.13.423.395.81q.264.388.707.765q.965.809 1.489 1.965T18 12q0 1.314-.524 2.47t-1.49 1.99q-.442.402-.706.786q-.264.385-.395.789l-.633 2.213q-.104.343-.372.547t-.61.205zm4.808-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463m-5.476-9.21q.519-.163.991-.248T12 5.994t.947.085t.991.248L13.27 4h-2.538zM10.73 20h2.538l.67-2.327q-.52.164-.992.236T12 17.98t-.947-.072t-.991-.236z");
}

</style>
