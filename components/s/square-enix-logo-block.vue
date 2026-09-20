<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pytm-kb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pytm-kb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:square-enix-logo-block" /></template>
