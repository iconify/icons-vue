<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugphw97q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hugphw97q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mug-saucer-outline" /></template>
