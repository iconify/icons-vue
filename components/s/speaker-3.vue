<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pup2v7bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pup2v7bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-3" /></template>
