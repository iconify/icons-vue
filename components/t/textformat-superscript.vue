<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umk9o8bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="umk9o8bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:textformat-superscript" /></template>
