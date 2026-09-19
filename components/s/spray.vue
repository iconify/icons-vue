<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emaxowpvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="emaxowpvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:spray" /></template>
