<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7m_yyd2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p7m_yyd2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:zoom-in-gesture-solid" /></template>
