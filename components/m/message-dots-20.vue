<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmoa867s.css';
import '../../css/n/nhhca1beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itmoa867s"/><path class="nhhca1beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-dots-20" /></template>
