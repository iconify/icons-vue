<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te3fbc6yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te3fbc6yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shield-ban" /></template>
