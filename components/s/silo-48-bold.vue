<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj89w9bur.css';
import '../../css/n/ndtj57bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pj89w9bur"/><path class="ndtj57bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silo-48-bold" /></template>
