<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9smel4pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p9smel4pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-menu-solid" /></template>
