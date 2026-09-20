<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q19e26bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q19e26bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:received" /></template>
