<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b86dbmu5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b86dbmu5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:subscript" /></template>
