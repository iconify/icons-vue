<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8ctqoumq.css';
import '../../css/e/e5-idrbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8ctqoumq"/><path class="e5-idrbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tablet-landscape" /></template>
