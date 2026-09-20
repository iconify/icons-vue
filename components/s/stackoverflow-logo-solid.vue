<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik_fsylgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik_fsylgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stackoverflow-logo-solid" /></template>
