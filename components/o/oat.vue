<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acg8dcc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="acg8dcc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:oat" /></template>
