<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfhurn1ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfhurn1ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-star" /></template>
