<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frj64eb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frj64eb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2018-light" /></template>
