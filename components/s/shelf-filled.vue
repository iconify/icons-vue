<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-9_s5i_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z-9_s5i_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shelf-filled" /></template>
