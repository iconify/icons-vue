<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpzqjrc-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gpzqjrc-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:staroflife-fill" /></template>
