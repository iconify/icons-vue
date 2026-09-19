<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8a9t6b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8a9t6b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nextdoor" /></template>
