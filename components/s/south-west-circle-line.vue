<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw0lxbcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw0lxbcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-circle-line" /></template>
