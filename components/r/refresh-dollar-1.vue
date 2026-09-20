<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giqgrriek.css';
import '../../css/e/ec7vxwnky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="giqgrriek"/><path class="ec7vxwnky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:refresh-dollar-1" /></template>
