<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tar6cn05y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tar6cn05y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:preview-close-one" /></template>
