<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9mb5epez.css';
import '../../css/o/ofnlx5qvz.css';
import '../../css/n/nciip6bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9mb5epez"/><path class="ofnlx5qvz"/><path class="nciip6bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-48-bold" /></template>
