<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eojz8nbhf.css';
import '../../css/l/lalcw8bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eojz8nbhf"/><path class="lalcw8bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refinery-48-bold" /></template>
