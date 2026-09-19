<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ago-3bcco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ago-3bcco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:testicles" /></template>
