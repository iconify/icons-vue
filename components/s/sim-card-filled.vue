<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suih8fnam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suih8fnam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sim-card-filled" /></template>
