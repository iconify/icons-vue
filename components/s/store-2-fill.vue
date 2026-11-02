<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcrwjbr4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcrwjbr4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-2-fill" /></template>
