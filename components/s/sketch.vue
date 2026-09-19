<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5krske9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a5krske9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sketch" /></template>
