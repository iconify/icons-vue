<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35p42bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j35p42bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:plane" /></template>
