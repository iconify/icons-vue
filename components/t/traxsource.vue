<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-6yrobrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-6yrobrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:traxsource" /></template>
