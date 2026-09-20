<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw2n0rlwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw2n0rlwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-fill" /></template>
