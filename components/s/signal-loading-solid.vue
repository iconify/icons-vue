<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdbm3gb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mdbm3gb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-loading-solid" /></template>
