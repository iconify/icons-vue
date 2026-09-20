<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i18is5bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i18is5bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scissors-filled" /></template>
