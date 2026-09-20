<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx4m1cb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx4m1cb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stumble-upong-1ing-logo-solid" /></template>
