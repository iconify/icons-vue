<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za_n_7bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za_n_7bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:point-out" /></template>
