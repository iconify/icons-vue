<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxtpv0web.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxtpv0web"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openmined" /></template>
