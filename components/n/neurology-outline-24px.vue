<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2hne7ojo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2hne7ojo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:neurology-outline-24px" /></template>
