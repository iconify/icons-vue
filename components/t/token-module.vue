<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l04k3h--y.css';
import '../../css/v/v1qrver_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l04k3h--y"/><path class="v1qrver_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-module" /></template>
