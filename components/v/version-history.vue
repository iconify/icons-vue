<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z521863aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z521863aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:version-history" /></template>
