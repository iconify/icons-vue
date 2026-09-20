<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc4l4ubwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-book" /></template>
<style>
.tc4l4ubwe {
  fill: currentColor;
  d: path("M8.766 16.91q-1.51.525-2.766 1.475v1q0 .25.173.432q.173.183.423.183h10.789q.269 0 .442-.173t.173-.442v-1q-1.275-.95-2.775-1.475T12 16.385t-3.234.525M6.615 21q-.672 0-1.144-.472T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616v14.769q0 .67-.472 1.143q-.472.472-1.143.472zm7.513-7.794q.871-.871.871-2.129t-.871-2.129T12 8.077t-2.129.871T9 11.077t.871 2.129t2.129.871t2.129-.871");
}

</style>
