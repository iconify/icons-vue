<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj06nrhcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj06nrhcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opencontainersinitiative" /></template>
