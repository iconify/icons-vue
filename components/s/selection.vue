<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os7nu960g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os7nu960g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:selection" /></template>
