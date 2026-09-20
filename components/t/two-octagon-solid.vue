<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6fgm95al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6fgm95al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:two-octagon-solid" /></template>
