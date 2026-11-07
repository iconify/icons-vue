<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_hwnn33g.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_hwnn33g"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pulse-outline" /></template>
