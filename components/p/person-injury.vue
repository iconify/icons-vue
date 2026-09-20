<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2iihgbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2iihgbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-injury" /></template>
