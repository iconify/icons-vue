<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fse9x8baa.css';
import '../../css/d/dlp7nstpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fse9x8baa"/><circle class="dlp7nstpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:server-dns" /></template>
