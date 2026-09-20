<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bawdkac8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bawdkac8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sort-desc-24" /></template>
