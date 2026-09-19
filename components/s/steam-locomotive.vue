<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7lavefjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a7lavefjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:steam-locomotive" /></template>
