<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgh_rbqn.css';
import '../../css/o/olx2f-b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="abgh_rbqn"/><path class="olx2f-b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scrubber-48-bold" /></template>
