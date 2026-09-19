<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsyop5ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqsyop5ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:text-slash-outline" /></template>
