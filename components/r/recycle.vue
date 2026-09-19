<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhxmg9bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhxmg9bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:recycle" /></template>
