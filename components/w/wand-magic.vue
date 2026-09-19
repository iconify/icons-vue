<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bib8c1wwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bib8c1wwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wand-magic" /></template>
