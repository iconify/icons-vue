<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an9bkgbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="an9bkgbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-large-outline" /></template>
