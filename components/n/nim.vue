<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6jc2nbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6jc2nbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nim" /></template>
