<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-lmpi58f.css';
import '../../css/u/uqtphxb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-lmpi58f"/><path class="uqtphxb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-waste-48-bold" /></template>
