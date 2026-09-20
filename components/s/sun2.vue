<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvzzvdbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvzzvdbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sun2" /></template>
