<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt9b6kjbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kt9b6kjbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ok-hand" /></template>
