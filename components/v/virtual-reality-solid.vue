<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl7fiqbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gl7fiqbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:virtual-reality-solid" /></template>
