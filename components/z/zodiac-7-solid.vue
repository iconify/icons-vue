<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btf2_ybvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="btf2_ybvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-7-solid" /></template>
