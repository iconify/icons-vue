<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3awlkbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-description-rtl-24-regular" /></template>
<style>
.y3awlkbak {
  fill: currentColor;
  d: path("M21.25 17H8.75a.75.75 0 0 0-.102 1.493l.102.007h12.5a.75.75 0 0 0 .102-1.493zH8.75zm0-4H2.75a.75.75 0 0 0-.102 1.493l.102.007h18.5a.75.75 0 0 0 .102-1.493zH2.75zm0-4H2.75a.75.75 0 0 0-.102 1.493l.102.007h18.5a.75.75 0 0 0 .102-1.493zH2.75zm0-4H2.75a.75.75 0 0 0-.102 1.493l.102.007h18.5a.75.75 0 0 0 .102-1.493zH2.75z");
}

</style>
