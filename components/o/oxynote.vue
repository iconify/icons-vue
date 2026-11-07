<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biu8trvyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="biu8trvyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oxynote" /></template>
