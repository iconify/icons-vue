<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyegqlb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jyegqlb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outdent-20" /></template>
