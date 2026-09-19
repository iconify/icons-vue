<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqi0klb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oqi0klb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:one-of-characters-mahjong" /></template>
