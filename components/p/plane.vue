<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tujo4e5-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tujo4e5-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:plane" /></template>
