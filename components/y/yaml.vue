<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rifvtfxit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":457,"height":512};
const content = `<path class="rifvtfxit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yaml" /></template>
