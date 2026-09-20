<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnjz_aczh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnjz_aczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-sharp-fill" /></template>
