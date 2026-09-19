<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r69m7kc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r69m7kc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pause-btn-fill" /></template>
