<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg91i5bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg91i5bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:mention" /></template>
