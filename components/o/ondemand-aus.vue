<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd67zjbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd67zjbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ondemand-aus" /></template>
