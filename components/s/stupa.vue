<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq7b1j2cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vq7b1j2cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:stupa" /></template>
