<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx29zvbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fx29zvbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-mail-light" /></template>
