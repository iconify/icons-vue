<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9qoumbuq.css';
import '../../css/b/batz7rxuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9qoumbuq"/><path class="batz7rxuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiredoor-light" /></template>
