<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpj3yzbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fpj3yzbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-smcp-small-filled" /></template>
