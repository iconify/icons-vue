<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj_287btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qj_287btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:menu" /></template>
