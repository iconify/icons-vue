<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfmtyirhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfmtyirhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-down-2-fill" /></template>
