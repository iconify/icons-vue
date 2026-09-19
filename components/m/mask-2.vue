<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9zbbnmpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="v9zbbnmpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mask-2" /></template>
