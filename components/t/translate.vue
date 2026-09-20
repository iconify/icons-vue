<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmez7gexu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmez7gexu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:translate" /></template>
