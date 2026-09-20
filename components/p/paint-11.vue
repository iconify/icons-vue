<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyezjvb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="lyezjvb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:paint-11" /></template>
