<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxwhn9bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nxwhn9bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zbrush" /></template>
