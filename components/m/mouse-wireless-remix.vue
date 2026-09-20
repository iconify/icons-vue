<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky9cn3brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ky9cn3brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mouse-wireless-remix" /></template>
