<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lozx6-brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lozx6-brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mushroom-1-filled" /></template>
