<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxh3rob4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1760};
const content = `<path class="uxh3rob4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:shirtsinbulk" /></template>
