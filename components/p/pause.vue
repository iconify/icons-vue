<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7znkhbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z7znkhbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:pause" /></template>
