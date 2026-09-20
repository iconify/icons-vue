<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj9lswfhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj9lswfhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oculus" /></template>
