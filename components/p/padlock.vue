<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8cc9ke3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="u8cc9ke3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:padlock" /></template>
