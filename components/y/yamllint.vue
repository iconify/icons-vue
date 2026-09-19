<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alm0-u9-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alm0-u9-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yamllint" /></template>
