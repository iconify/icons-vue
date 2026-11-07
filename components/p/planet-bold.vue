<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfi_pwizc.css';
import '../../css/t/tc8lqywfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfi_pwizc"/><path class="tc8lqywfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-bold" /></template>
