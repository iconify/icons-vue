<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iysnah-wi.css';
import '../../css/u/u3dxucb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iysnah-wi"/><path class="u3dxucb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:set-square-48-bold" /></template>
