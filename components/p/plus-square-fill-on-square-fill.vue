<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6vgv7b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f6vgv7b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-square-fill-on-square-fill" /></template>
