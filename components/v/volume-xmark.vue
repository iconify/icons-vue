<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrr9o3jlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrr9o3jlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:volume-xmark" /></template>
