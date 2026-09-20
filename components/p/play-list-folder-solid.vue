<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrew4e9yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vrew4e9yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:play-list-folder-solid" /></template>
