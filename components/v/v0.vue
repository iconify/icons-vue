<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlyr80z1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlyr80z1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:v0" /></template>
