<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0f10gbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0f10gbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:r" /></template>
