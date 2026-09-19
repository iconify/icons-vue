<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_--sqbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_--sqbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:read-the-docs" /></template>
