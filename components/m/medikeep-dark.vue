<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkzqvsb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkzqvsb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medikeep-dark" /></template>
