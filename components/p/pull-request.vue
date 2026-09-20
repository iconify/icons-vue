<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_rrezb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_rrezb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pull-request" /></template>
