<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijab_1a-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ijab_1a-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:theater-mask-solid" /></template>
