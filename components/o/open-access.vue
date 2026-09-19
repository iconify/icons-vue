<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_-7xubde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_-7xubde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:open-access" /></template>
