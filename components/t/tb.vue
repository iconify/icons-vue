<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwingb7ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kwingb7ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tb" /></template>
