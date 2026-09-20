<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od_h8eb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od_h8eb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:yen-circle" /></template>
