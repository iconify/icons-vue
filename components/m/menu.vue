<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7qf6bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="lu7qf6bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:menu" /></template>
