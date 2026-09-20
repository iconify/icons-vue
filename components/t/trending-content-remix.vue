<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwl4lns9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pwl4lns9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:trending-content-remix" /></template>
