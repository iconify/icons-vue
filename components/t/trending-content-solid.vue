<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8v_ijbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f8v_ijbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:trending-content-solid" /></template>
