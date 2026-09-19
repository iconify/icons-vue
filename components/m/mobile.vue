<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lfj-bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="l3lfj-bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mobile" /></template>
