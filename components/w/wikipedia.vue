<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz71dbktw.css';
import '../../css/r/rytfiabwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vz71dbktw"/><path class="rytfiabwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:wikipedia" /></template>
