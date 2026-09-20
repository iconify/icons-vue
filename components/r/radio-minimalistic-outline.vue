<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylpz7_bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylpz7_bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radio-minimalistic-outline" /></template>
