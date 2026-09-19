<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt-zv9ths.css';
import '../../css/u/uzucf_p2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pt-zv9ths"/><path class="uzucf_p2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-avatar" /></template>
