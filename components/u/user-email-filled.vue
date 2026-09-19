<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu2f4lpfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu2f4lpfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-email-filled" /></template>
