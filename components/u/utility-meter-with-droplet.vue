<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsqhrhbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vsqhrhbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-meter-with-droplet" /></template>
