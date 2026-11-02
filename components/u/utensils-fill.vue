<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch6k0bq6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch6k0bq6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:utensils-fill" /></template>
