<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh03m-bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh03m-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-people-user-bubble-circle" /></template>
