<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6r-ysfqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6r-ysfqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:withoutbg" /></template>
