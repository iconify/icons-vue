<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1dnnyevj.css';
import '../../css/v/v1iup-t3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1dnnyevj"/><path class="v1iup-t3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mug-48-bold" /></template>
