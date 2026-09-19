<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrcfhl16j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrcfhl16j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:moleculer" /></template>
