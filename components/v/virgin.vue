<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqe27cb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqe27cb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:virgin" /></template>
