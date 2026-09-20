<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu480nb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu480nb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rollupjs" /></template>
