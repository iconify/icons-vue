<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9s39grzg.css';
import '../../css/e/eueslcc2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9s39grzg"/><path class="eueslcc2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-bottle-48" /></template>
