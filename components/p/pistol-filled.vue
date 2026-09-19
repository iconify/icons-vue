<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pishw9bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pishw9bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pistol-filled" /></template>
