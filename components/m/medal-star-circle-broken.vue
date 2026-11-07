<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xekr-cc0r.css';
import '../../css/a/azsj7yb9j.css';
import '../../css/q/qxdu-bceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xekr-cc0r"/><path class="azsj7yb9j"/><path class="qxdu-bceo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-circle-broken" /></template>
