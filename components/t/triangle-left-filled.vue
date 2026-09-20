<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjk-fj_rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jjk-fj_rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-left-filled" /></template>
