<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl6-5w16k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl6-5w16k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:watering-soil" /></template>
