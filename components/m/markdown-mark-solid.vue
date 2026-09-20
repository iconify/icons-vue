<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz1np5bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cz1np5bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:markdown-mark-solid" /></template>
