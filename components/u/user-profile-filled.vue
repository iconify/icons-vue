<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd57ugbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd57ugbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-profile-filled" /></template>
