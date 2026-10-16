<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kllrszb1h.css';
import '../../css/k/kknmzu6wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kllrszb1h"/><path class="kknmzu6wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:or-gate-48-bold" /></template>
