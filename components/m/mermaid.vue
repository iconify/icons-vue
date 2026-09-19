<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inzdrrbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":367,"height":512};
const content = `<path class="inzdrrbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mermaid" /></template>
