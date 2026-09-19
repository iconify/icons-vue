<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfo43fa_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vfo43fa_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-digging" /></template>
