<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b97mt4bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b97mt4bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:outlet-2-line" /></template>
