<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulfxfjbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulfxfjbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:path-fill-round" /></template>
