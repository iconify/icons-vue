<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq59lj-wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq59lj-wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wrench-check" /></template>
