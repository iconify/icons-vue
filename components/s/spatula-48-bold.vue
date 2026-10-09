<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3svyccwt.css';
import '../../css/u/us2y8_bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3svyccwt"/><path class="us2y8_bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spatula-48-bold" /></template>
