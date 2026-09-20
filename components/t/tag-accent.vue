<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coig8-25c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coig8-25c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:tag-accent" /></template>
