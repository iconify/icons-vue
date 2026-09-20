<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cszz9xbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:router-off-outline" /></template>
<style>
.cszz9xbow {
  fill: currentColor;
  d: path("m14.289 8.404l-.72-.72q.65-.6 1.335-.892t1.48-.292t1.481.292t1.335.893l-.72.719q-.426-.427-.94-.665q-.515-.239-1.155-.239t-1.155.239t-.942.665m-2.5-2.5l-.707-.708q1.042-1.042 2.386-1.619T16.384 3q1.574 0 2.918.577t2.387 1.62l-.708.707q-.825-.825-1.99-1.364Q17.827 4 16.384 4q-1.442 0-2.606.54q-1.165.539-1.99 1.364M20 17.708l-4.115-4.116V10h1v4h1.5q.69 0 1.153.463T20 15.616zM5.616 19h11.438l-4-4H5.616q-.27 0-.443.173T5 15.616v2.769q0 .269.173.442t.443.173m13.698 2.26L18.054 20H5.616q-.691 0-1.153-.462T4 18.384v-2.768q0-.691.463-1.153T5.616 14h6.438L2.22 4.167l.713-.713l17.093 17.092zM6.45 17.549q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22m3.5 0q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22m3.5 0q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22M5 19v-4z");
}

</style>
