<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwvhx2bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwvhx2bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:unlock-alt-solid" /></template>
