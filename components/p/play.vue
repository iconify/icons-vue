<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7yn7fqdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7yn7fqdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:play" /></template>
