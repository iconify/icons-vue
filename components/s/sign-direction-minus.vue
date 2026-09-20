<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo_bipbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo_bipbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sign-direction-minus" /></template>
