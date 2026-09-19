<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgyfhabmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgyfhabmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pbs" /></template>
