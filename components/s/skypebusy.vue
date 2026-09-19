<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfxlr7j4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jfxlr7j4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:skypebusy" /></template>
