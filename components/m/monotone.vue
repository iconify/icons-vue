<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r10w3649d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":415,"height":512};
const content = `<path class="r10w3649d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:monotone" /></template>
