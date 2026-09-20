<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx2_oc7fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx2_oc7fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pulse-line" /></template>
