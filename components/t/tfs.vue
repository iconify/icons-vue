<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao1ao21el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":510,"height":512};
const content = `<path class="ao1ao21el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tfs" /></template>
