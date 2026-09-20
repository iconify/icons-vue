<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcpa5tpzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vcpa5tpzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:speaker" /></template>
