<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9rze1izo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="a9rze1izo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:swap-vertical-arrows-outline" /></template>
