<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe0ub5oav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe0ub5oav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-office-dark" /></template>
