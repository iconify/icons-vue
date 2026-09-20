<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gurr32bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gurr32bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-envelope-remix" /></template>
