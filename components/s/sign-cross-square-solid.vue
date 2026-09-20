<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bup17yboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bup17yboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sign-cross-square-solid" /></template>
