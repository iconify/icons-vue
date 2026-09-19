<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4x3cd_oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":472};
const content = `<path class="a4x3cd_oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wb-iridescent" /></template>
