<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcq7sn2qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcq7sn2qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mic2" /></template>
