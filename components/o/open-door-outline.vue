<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyvh2j2cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyvh2j2cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:open-door-outline" /></template>
