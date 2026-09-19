<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3469cbxe.css';
import '../../css/n/n8ytkn-vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3469cbxe"/><path class="n8ytkn-vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view" /></template>
