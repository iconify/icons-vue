<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcld88i4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcld88i4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:toggle-off" /></template>
