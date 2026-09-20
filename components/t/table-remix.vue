<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1izyrteh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s1izyrteh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:table-remix" /></template>
