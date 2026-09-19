<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7g52cc-s.css';
import '../../css/p/pftszrbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7g52cc-s"/><path class="pftszrbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:opened-folder" /></template>
