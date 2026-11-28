<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkipm3bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gkipm3bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-plus-thin" /></template>
