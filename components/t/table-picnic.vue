<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_jrtztkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_jrtztkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-picnic" /></template>
