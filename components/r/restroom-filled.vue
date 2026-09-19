<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erm34rd6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="erm34rd6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:restroom-filled" /></template>
