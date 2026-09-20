<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz288ab_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz288ab_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server3-filled" /></template>
