<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3um0j9hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x3um0j9hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:whmcs" /></template>
