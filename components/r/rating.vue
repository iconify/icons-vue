<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfvx-db7p.css';
import '../../css/e/ecev0ub1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kfvx-db7p"/><path class="ecev0ub1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:rating" /></template>
