<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg00kur-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pg00kur-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:signal-full-remix" /></template>
