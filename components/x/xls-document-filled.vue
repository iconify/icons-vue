<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je8ik9x9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="je8ik9x9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:xls-document-filled" /></template>
