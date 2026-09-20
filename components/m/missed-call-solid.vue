<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f21njubci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f21njubci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:missed-call-solid" /></template>
