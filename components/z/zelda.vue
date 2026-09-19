<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1_2w54z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":896};
const content = `<path class="he1_2w54z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zelda" /></template>
