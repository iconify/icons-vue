<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0o0atbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0o0atbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stop-circle-solid" /></template>
