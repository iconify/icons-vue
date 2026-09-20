<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww-hxrbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww-hxrbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wikimedia-commons" /></template>
