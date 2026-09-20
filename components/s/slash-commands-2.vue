<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg414d5aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg414d5aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slash-commands-2" /></template>
