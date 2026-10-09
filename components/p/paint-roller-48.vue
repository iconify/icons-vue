<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x813rhndo.css';
import '../../css/n/nvr1vcb4k.css';
import '../../css/b/bc-b47bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x813rhndo"/><path class="nvr1vcb4k"/><path class="bc-b47bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paint-roller-48" /></template>
