<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_7wlkbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_7wlkbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:shield-alt" /></template>
