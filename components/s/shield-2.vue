<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byzn4abda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="byzn4abda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-2" /></template>
