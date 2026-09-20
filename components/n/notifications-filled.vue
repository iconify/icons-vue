<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtnf79b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mtnf79b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:notifications-filled" /></template>
