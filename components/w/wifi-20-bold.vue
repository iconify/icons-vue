<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvj1k6p0o.css';
import '../../css/h/h5d_4v8si.css';
import '../../css/x/xsz5ie_ke.css';
import '../../css/f/f5h10_v-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zvj1k6p0o"/><path class="h5d_4v8si"/><path class="xsz5ie_ke"/><path class="f5h10_v-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-20-bold" /></template>
