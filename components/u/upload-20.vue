<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn4hkfpso.css';
import '../../css/u/un40bqbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dn4hkfpso"/><path class="un40bqbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-20" /></template>
