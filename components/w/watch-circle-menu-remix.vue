<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td2jlvbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="td2jlvbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:watch-circle-menu-remix" /></template>
