<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjssjrx3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjssjrx3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-round" /></template>
