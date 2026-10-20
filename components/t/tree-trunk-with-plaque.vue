<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvuhsqg_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jvuhsqg_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tree-trunk-with-plaque" /></template>
