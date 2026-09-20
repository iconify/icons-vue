<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrc8hdnnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rrc8hdnnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:podium" /></template>
