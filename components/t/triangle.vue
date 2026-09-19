<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bshgn5bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bshgn5bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:triangle" /></template>
