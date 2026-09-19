<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwev2pbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwev2pbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:polestar" /></template>
