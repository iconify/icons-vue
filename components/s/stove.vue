<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8z_ehb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="q8z_ehb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:stove" /></template>
