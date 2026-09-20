<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p540hcswf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p540hcswf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-box-1-solid" /></template>
