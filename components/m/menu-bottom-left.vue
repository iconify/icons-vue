<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if7f6bbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="if7f6bbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-bottom-left" /></template>
