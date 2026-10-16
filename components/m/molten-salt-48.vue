<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-wxdblp.css';
import '../../css/x/xl5sv-boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="xl5sv-boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:molten-salt-48" /></template>
