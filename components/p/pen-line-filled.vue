<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phg7sez3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phg7sez3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-line-filled" /></template>
