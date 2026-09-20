<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui42f08vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui42f08vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tennis-ball-outline" /></template>
