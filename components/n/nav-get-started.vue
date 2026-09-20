<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbn1uy2ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kbn1uy2ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-get-started" /></template>
