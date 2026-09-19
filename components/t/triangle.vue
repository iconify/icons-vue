<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyrwcnj9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zyrwcnj9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:triangle" /></template>
