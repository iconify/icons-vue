<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3dv8bc_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3dv8bc_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sigma" /></template>
