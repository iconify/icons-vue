<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac77tjbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ac77tjbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:two-arrow-in-down-up" /></template>
