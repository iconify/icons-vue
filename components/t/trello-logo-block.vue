<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwt6dac6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwt6dac6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:trello-logo-block" /></template>
