<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_debboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk_debboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:send" /></template>
