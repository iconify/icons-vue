<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvv8_0b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xvv8_0b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:table-solid" /></template>
