<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6atupb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v6atupb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:prisoner" /></template>
