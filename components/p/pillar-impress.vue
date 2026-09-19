<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg_meg-on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg_meg-on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pillar-impress" /></template>
