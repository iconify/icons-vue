<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xemwnbqyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xemwnbqyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:search" /></template>
