<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oig4oxbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="oig4oxbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mocule" /></template>
