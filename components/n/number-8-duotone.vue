<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6e5x5bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6e5x5bmc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-8-duotone" /></template>
