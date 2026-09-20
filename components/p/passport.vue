<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui12pvbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui12pvbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:passport" /></template>
