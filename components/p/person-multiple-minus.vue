<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjhnb3boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjhnb3boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-multiple-minus" /></template>
