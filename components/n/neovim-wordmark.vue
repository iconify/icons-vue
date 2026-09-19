<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmy2s3qlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kmy2s3qlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:neovim-wordmark" /></template>
