<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovh4bhbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovh4bhbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sitecore" /></template>
