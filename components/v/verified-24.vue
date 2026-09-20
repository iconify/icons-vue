<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bspz8r2wy.css';
import '../../css/s/s-uxakxfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bspz8r2wy"/><path class="s-uxakxfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:verified-24" /></template>
