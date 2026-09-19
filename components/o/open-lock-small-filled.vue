<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gums8tbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gums8tbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:open-lock-small-filled" /></template>
