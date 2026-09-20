<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2_p21wcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2_p21wcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sidebar-right2-filled" /></template>
