<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id5a9xwyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="id5a9xwyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volleyball-ball" /></template>
