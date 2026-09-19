<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbeeyzlid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbeeyzlid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:octopus-deploy" /></template>
