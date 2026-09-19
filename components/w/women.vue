<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkv_76b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkv_76b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:women" /></template>
