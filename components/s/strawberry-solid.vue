<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhhu3qfns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jhhu3qfns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:strawberry-solid" /></template>
