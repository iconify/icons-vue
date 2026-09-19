<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwu_-mu-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zwu_-mu-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-folder-outline" /></template>
