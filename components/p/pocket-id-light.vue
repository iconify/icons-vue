<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao5mpybbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ao5mpybbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-id-light" /></template>
