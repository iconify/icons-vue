<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6zlxdrk.css';
import '../../css/w/wp13yub7p.css';
import '../../css/c/cl2lae65c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia6zlxdrk"/><path class="wp13yub7p"/><path class="cl2lae65c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-48-bold" /></template>
