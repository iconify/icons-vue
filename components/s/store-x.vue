<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjhkc9akx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjhkc9akx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:store-x" /></template>
