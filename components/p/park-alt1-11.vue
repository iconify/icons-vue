<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1zhkdvnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="p1zhkdvnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:park-alt1-11" /></template>
