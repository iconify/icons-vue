<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-p_ha-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh-p_ha-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:sun" /></template>
