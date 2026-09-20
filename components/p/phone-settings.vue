<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-gyo5uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-gyo5uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-settings" /></template>
