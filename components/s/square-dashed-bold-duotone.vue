<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2sk80bby.css';
import '../../css/f/fbnpbdb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2sk80bby"/><path class="fbnpbdb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-dashed-bold-duotone" /></template>
