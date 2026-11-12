<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxhu2qlhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxhu2qlhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-pen" /></template>
