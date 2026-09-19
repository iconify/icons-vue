<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltdl5wbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltdl5wbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:playlist-add" /></template>
