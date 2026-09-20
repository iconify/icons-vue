<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6l5_2szw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6l5_2szw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-rotate" /></template>
