<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh7_gacbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh7_gacbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-warning-solid" /></template>
