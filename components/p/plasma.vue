<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wji3m3b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wji3m3b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:plasma" /></template>
