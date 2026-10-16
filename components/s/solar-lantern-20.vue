<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii45op72q.css';
import '../../css/m/mfv2n_b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ii45op72q"/><path class="mfv2n_b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-lantern-20" /></template>
