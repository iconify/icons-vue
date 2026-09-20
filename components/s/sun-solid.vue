<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz-t0mr5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mz-t0mr5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sun-solid" /></template>
