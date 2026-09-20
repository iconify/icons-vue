<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij19_zngc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ij19_zngc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trash-restore-alt-solid" /></template>
