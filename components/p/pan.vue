<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b49e83bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b49e83bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pan" /></template>
