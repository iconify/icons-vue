<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2lf81ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2lf81ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sos-sign-bold" /></template>
