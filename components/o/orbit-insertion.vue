<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_9hj823f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:orbit-insertion" /></template>
<style>
.v_9hj823f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.755 10.684q.107-3.214 2.411-5.518Q9.583 2.75 13 2.75t5.834 2.416T21.25 11t-2.416 5.834Q16.417 19.25 13 19.25t-5.834-2.416q-.795-.795-1.328-1.699q-.619 3.104-2.167 6.2q-.067.134-.18.232q-.112.097-.254.145q-.141.047-.29.036q-.149-.01-.282-.077q-.066-.033-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137q1.943-3.886 2.327-7.76l-.876.875q-.052.053-.113.094t-.13.069t-.141.043T3.25 14t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.106-.105-.163-.243T2.5 13.25t.057-.287t.163-.243zM9.75 11q0 3.25 3.25 3.25q1.346 0 2.298-.952T16.25 11t-.952-2.298T13 7.75q-3.25 0-3.25 3.25");
}

</style>
