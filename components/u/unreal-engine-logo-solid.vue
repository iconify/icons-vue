<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rho4i-b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rho4i-b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:unreal-engine-logo-solid" /></template>
