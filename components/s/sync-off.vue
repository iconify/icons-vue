<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsx3ph7fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsx3ph7fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sync-off" /></template>
