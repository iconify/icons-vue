<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt2n2mulw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zt2n2mulw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-inverted-medium-outline" /></template>
