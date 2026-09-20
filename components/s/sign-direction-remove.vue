<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtpbjcxwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtpbjcxwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sign-direction-remove" /></template>
