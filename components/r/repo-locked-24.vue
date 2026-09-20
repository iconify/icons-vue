<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwb2ztm3s.css';
import '../../css/s/sz-8khbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwb2ztm3s"/><path class="sz-8khbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-locked-24" /></template>
