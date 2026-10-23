<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g75l-ibgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g75l-ibgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-minus" /></template>
