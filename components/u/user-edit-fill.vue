<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8z7lgbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8z7lgbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-edit-fill" /></template>
