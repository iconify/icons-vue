<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3imv28ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3imv28ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:triangular-flag-fill" /></template>
