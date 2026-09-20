<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbtg5fbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dbtg5fbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:visual-blind-solid" /></template>
