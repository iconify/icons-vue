<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzwavbc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rzwavbc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:qwiklabs" /></template>
