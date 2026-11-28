<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcxaaqz_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcxaaqz_m primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-2-duotone" /></template>
