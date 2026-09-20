<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh-7kfbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-7kfbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slash-fill" /></template>
