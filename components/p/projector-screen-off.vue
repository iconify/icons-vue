<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlllpobll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlllpobll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:projector-screen-off" /></template>
