<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da74jmbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="da74jmbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:sort-alt" /></template>
