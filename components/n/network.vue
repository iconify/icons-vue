<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osyb__p_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osyb__p_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:network" /></template>
