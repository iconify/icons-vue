<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glrde1b3i.css';
import '../../css/h/hgi3nccbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="glrde1b3i"/><path class="hgi3nccbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pill-48" /></template>
