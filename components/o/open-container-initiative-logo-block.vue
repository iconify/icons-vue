<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywec42b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywec42b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:open-container-initiative-logo-block" /></template>
