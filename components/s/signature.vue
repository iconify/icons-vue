<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klawgabfn.css';
import '../../css/e/e0z7xwbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="klawgabfn"/><path class="e0z7xwbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:signature" /></template>
