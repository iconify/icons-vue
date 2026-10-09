<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86gyghte.css';
import '../../css/n/nkn0wyb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r86gyghte"/><path class="nkn0wyb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-48-bold" /></template>
