<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg24un7vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fg24un7vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:small-plane-outline" /></template>
