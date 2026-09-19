<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj-rdigue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj-rdigue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:security-camera-filled" /></template>
