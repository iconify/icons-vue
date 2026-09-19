<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dofh-nm5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dofh-nm5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tent-outline" /></template>
