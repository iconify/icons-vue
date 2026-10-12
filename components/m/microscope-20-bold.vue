<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpk6ucc_d.css';
import '../../css/z/zm70e2bpm.css';
import '../../css/c/ciep4282w.css';
import '../../css/n/nxoc-wizh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lpk6ucc_d"/><path class="zm70e2bpm"/><path class="ciep4282w"/><path class="nxoc-wizh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microscope-20-bold" /></template>
