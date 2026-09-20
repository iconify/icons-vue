<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-pgsfpfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h-pgsfpfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-filled" /></template>
