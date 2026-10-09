<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr10-cc_e.css';
import '../../css/s/s27104b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mr10-cc_e"/><path class="s27104b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skyscraper-48" /></template>
