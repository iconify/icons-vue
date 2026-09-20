<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndp3-e9tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ndp3-e9tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:zoom-in-gesture-remix" /></template>
