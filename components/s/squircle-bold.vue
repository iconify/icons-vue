<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8uot5bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a8uot5bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:squircle-bold" /></template>
