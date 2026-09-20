<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egmvb8bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egmvb8bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reminder" /></template>
