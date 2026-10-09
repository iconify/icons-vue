<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnjcr8b9t.css';
import '../../css/f/f7_sevb3w.css';
import '../../css/a/a8x12iari.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnjcr8b9t"/><path class="f7_sevb3w"/><path class="a8x12iari"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rcd-48-bold" /></template>
