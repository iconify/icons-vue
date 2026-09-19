<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoqkbjeqd.css';
import '../../css/c/cpe-z9b0s.css';
import '../../css/d/dj01mremq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yoqkbjeqd"/><path class="cpe-z9b0s"/><path class="dj01mremq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:plotly" /></template>
