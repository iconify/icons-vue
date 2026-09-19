<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3sxunm-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="v3sxunm-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rouble" /></template>
