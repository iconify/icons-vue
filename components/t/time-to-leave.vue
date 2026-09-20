<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc7hk3brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc7hk3brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:time-to-leave" /></template>
