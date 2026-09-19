<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9sgzxuyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f9sgzxuyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:palm-branches-roof-outline" /></template>
