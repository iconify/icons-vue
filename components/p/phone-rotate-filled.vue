<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tywuk3btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tywuk3btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-rotate-filled" /></template>
