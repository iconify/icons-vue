<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd2ixsb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2ixsb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spell-check-solid" /></template>
