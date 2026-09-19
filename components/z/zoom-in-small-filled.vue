<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxum_g7ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hxum_g7ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zoom-in-small-filled" /></template>
