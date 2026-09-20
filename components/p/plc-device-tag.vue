<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjki5abjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fjki5abjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plc-device-tag" /></template>
