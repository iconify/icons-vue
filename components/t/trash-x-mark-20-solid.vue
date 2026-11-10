<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn9bxqalx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wn9bxqalx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-x-mark-20-solid" /></template>
