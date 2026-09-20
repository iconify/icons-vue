<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5r444b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5r444b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:temperature-fill" /></template>
