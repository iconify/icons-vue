<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-nvybc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-nvybc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:origin-logo-block" /></template>
