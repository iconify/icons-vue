<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d__i3j54m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d__i3j54m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slightly-smiling-face-small" /></template>
