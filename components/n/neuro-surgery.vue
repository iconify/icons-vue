<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhohgab5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bhohgab5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:neuro-surgery" /></template>
