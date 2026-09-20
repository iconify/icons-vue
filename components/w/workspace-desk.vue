<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siu7-7lbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="siu7-7lbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:workspace-desk" /></template>
