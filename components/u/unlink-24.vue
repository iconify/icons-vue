<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp1q85cys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp1q85cys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unlink-24" /></template>
