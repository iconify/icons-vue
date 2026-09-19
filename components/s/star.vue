<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lywexebzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lywexebzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:star" /></template>
