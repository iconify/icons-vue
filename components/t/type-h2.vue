<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjacrgb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pjacrgb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h2" /></template>
