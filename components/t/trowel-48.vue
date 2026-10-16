<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thafg6bsi.css';
import '../../css/q/qglubxbcs.css';
import '../../css/l/lnfvw2unm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thafg6bsi"/><path class="qglubxbcs"/><path class="lnfvw2unm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trowel-48" /></template>
