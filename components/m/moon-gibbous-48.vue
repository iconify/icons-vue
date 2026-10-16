<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_zzgnel.css';
import '../../css/c/c3wcvtp6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="c3wcvtp6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-gibbous-48" /></template>
