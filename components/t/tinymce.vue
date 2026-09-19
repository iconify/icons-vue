<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp5npu6fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rp5npu6fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tinymce" /></template>
