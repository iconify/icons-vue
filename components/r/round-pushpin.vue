<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsxa_fqyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vsxa_fqyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:round-pushpin" /></template>
