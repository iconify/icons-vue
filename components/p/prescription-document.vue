<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a54rpy29c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="a54rpy29c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:prescription-document" /></template>
