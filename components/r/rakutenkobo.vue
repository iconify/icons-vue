<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef0a_xk9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef0a_xk9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rakutenkobo" /></template>
