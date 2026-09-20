<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc_eovf9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pc_eovf9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:phone-filled" /></template>
