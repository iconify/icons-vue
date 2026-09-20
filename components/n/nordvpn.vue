<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuqzlyblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqzlyblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nordvpn" /></template>
