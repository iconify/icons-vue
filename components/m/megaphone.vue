<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osqul7bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osqul7bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:megaphone" /></template>
