<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my2u87bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="my2u87bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-vibrate-filled" /></template>
