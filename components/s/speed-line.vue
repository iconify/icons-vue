<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebvtjz36o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebvtjz36o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speed-line" /></template>
