<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fruy2eb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fruy2eb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:move-one" /></template>
