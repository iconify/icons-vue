<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tawnownbk.css';
import '../../css/l/lha6blb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tawnownbk"/><path class="lha6blb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:request-quote" /></template>
