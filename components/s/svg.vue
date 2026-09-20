<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3s_77bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3s_77bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:svg" /></template>
