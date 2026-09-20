<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuhlkkm_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fuhlkkm_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ringing-bell-notification" /></template>
