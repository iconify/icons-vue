<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o08-cac6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o08-cac6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-outline" /></template>
