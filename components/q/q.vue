<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhx0khm2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rhx0khm2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:q" /></template>
