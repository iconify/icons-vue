<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy4n6yuzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qy4n6yuzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:proper-roof2x-outline" /></template>
