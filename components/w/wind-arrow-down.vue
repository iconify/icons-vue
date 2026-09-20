<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8u35khax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8u35khax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wind-arrow-down" /></template>
