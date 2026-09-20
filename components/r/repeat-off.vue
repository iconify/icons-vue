<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjsf23bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjsf23bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:repeat-off" /></template>
