<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcusd5bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcusd5bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:question" /></template>
