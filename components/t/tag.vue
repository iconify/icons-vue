<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_08yzbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":504};
const content = `<path class="z_08yzbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:tag" /></template>
