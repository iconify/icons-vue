<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_146bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_146bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:qr-code" /></template>
