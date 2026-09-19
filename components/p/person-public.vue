<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhuhh32fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bhuhh32fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:person-public" /></template>
