<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z21k9mb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z21k9mb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:prompt-solid" /></template>
