<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw77ssi0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uw77ssi0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-right-up-filled" /></template>
