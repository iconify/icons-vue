<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shgrc6-hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="shgrc6-hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-2-fill" /></template>
