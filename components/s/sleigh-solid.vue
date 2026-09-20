<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcsa_x5rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vcsa_x5rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sleigh-solid" /></template>
