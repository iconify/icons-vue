<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6-00h62g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6-00h62g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-wave-filled" /></template>
