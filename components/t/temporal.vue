<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjn2c_7rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjn2c_7rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:temporal" /></template>
