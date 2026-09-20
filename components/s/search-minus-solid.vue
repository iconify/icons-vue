<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hawe5uj-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hawe5uj-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-minus-solid" /></template>
