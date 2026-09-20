<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_dx3d6ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_dx3d6ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-10-small" /></template>
