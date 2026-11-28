<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk3u-db7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk3u-db7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:settings-x" /></template>
