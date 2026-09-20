<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhcwarbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhcwarbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-edit3-filled" /></template>
