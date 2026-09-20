<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6xb5abaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6xb5abaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sunset" /></template>
