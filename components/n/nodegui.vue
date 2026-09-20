<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-m_ziyof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-m_ziyof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nodegui" /></template>
