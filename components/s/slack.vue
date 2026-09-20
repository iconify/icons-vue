<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwcjd133n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwcjd133n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:slack" /></template>
