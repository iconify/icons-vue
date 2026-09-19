<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phbn-6bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="phbn-6bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:triangle-down" /></template>
