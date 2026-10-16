<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mner4y11d.css';
import '../../css/i/ibp47861c.css';
import '../../css/m/mkkw_jb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mner4y11d"/><path class="ibp47861c"/><path class="mkkw_jb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tiny-house-48-bold" /></template>
