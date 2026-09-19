<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbv9h06jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbv9h06jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:phone" /></template>
