<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4nglabjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4nglabjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:upload-document-note" /></template>
