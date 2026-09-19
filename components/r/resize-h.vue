<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noys57btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="noys57btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:resize-h" /></template>
