<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_exxfftc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_exxfftc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-badge-alert" /></template>
