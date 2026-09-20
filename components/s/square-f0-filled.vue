<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvb01wb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvb01wb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-f0-filled" /></template>
