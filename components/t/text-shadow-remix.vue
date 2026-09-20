<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnbjt-bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jnbjt-bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-shadow-remix" /></template>
