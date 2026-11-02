<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltj7jfb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltj7jfb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-half-fill" /></template>
