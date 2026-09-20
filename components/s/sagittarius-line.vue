<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cssa9abid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cssa9abid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sagittarius-line" /></template>
