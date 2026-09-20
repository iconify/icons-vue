<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6edjb7-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a6edjb7-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tick-small-solid" /></template>
