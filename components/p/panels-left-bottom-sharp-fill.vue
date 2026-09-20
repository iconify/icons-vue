<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb4xki1ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb4xki1ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-left-bottom-sharp-fill" /></template>
