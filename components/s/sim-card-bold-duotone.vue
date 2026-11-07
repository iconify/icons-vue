<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-vry1bva.css';
import '../../css/z/za4fsnh-m.css';
import '../../css/m/m10r4ya4l.css';
import '../../css/y/y1djb4dsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-vry1bva"/><path class="za4fsnh-m"/><path class="m10r4ya4l"/><path class="y1djb4dsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-card-bold-duotone" /></template>
