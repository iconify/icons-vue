<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhon04bki.css';
import '../../css/o/ouolnv3pk.css';
import '../../css/s/sx8yv1e2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhon04bki"/><path class="ouolnv3pk"/><path class="sx8yv1e2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:openapi" /></template>
