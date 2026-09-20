<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jquahdb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jquahdb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:moon-stars-remix" /></template>
