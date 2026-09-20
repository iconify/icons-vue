<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3mj-ds_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3mj-ds_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-73-small" /></template>
