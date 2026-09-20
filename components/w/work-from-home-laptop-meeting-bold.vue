<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoga5ubay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uoga5ubay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:work-from-home-laptop-meeting-bold" /></template>
