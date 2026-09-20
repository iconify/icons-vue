<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ebo54iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8ebo54iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mkvpriority-light" /></template>
