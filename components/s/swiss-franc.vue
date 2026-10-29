<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ab_21tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ab_21tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:swiss-franc" /></template>
