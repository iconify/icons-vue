<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prmy9wtgl.css';
import '../../css/m/miwt5_b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prmy9wtgl"/><path class="miwt5_b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:senlo-light" /></template>
