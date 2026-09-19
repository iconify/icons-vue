<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhxqyqb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uhxqyqb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sad-cry-bold" /></template>
