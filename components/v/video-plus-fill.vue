<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhglu9bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhglu9bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-plus-fill" /></template>
