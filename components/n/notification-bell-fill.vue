<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkul2mbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkul2mbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-fill" /></template>
