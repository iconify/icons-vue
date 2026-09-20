<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrrckuble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrrckuble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-people-person-bubble-circle-1" /></template>
