<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsu46ub4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsu46ub4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-arrow-down-filled" /></template>
