<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i18y50gyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i18y50gyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-bold" /></template>
