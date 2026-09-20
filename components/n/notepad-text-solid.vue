<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ois0iqb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ois0iqb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:notepad-text-solid" /></template>
