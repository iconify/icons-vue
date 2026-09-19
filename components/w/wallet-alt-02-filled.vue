<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnune9bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnune9bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wallet-alt-02-filled" /></template>
