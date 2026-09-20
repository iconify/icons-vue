<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdtx07bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtx07bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:settings-24" /></template>
