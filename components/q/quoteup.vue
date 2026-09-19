<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frf7sf2bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="frf7sf2bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:quoteup" /></template>
