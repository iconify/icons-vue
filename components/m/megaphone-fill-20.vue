<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikj9gwsrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ikj9gwsrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:megaphone-fill-20" /></template>
