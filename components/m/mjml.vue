<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8z5myb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s8z5myb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mjml" /></template>
