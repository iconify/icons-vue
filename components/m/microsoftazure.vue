<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhasg7beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhasg7beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftazure" /></template>
