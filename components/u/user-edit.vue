<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d98qsujru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d98qsujru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:user-edit" /></template>
