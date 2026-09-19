<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea-m_ab_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ea-m_ab_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:travel" /></template>
