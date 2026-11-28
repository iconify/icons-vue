<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m60pqtldl.css';
import '../../css/s/sui4_vb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m60pqtldl secondary"/><path class="primary sui4_vb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-duo" /></template>
