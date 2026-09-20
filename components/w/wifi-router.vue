<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyf7m_beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyf7m_beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wifi-router" /></template>
