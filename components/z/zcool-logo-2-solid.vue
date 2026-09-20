<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ttaytlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0ttaytlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zcool-logo-2-solid" /></template>
