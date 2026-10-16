<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgmleib2q.css';
import '../../css/l/lw9-dbcju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgmleib2q"/><path class="lw9-dbcju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terraced-house-48-bold" /></template>
