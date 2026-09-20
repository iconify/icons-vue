<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz_34wb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz_34wb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:youtube" /></template>
