<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeey5wbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeey5wbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:overhead-projector-off" /></template>
