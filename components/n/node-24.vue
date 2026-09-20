<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8s5ksbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8s5ksbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:node-24" /></template>
