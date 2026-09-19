<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaw1tfb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qaw1tfb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-fill-16" /></template>
