<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqzpwybhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqzpwybhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:u-turn-sign-bold" /></template>
