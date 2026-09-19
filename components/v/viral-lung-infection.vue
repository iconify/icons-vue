<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnwisc42e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pnwisc42e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:viral-lung-infection" /></template>
