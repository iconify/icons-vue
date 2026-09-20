<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3htac5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-dock-outline-rounded" /></template>
<style>
.wa3htac5u {
  fill: currentColor;
  d: path("M16.192 16.385V3.614q0-.269-.173-.442T15.577 3H8.423q-.27 0-.442.173q-.173.173-.173.443v12.769q0 .269.173.442t.442.173h7.154q.27 0 .442-.173q.173-.173.173-.443M12.588 6.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22m-4.78 10.298V17V3zM8.423 18q-.666 0-1.14-.475t-.475-1.14V3.615q0-.666.474-1.14T8.423 2h7.154q.666 0 1.14.475t.475 1.14v2.127q.31-.001.52.242t.211.549v1.28q0 .307-.21.55q-.211.243-.52.24v7.782q0 .666-.475 1.14T15.577 18zM9 21.52q-.213 0-.356-.145T8.5 21.02t.144-.356T9 20.52h6q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143z");
}

</style>
