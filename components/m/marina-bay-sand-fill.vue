<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beg9a409b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beg9a409b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:marina-bay-sand-fill" /></template>
