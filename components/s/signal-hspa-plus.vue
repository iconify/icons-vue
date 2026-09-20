<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2g9l0aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2g9l0aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-hspa-plus" /></template>
