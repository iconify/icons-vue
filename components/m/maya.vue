<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbptlmbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jbptlmbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:maya" /></template>
