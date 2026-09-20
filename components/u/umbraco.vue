<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efg_z3lhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efg_z3lhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbraco" /></template>
