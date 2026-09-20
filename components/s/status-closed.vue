<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0o6xb60y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q0o6xb60y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-closed" /></template>
