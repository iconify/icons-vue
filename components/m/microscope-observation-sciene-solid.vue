<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqt06ac5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cqt06ac5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:microscope-observation-sciene-solid" /></template>
