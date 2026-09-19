<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf-a1damf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wf-a1damf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:n" /></template>
