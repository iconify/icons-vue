<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3zhikb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3zhikb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:refresh" /></template>
