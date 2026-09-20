<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuw3jibtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kuw3jibtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-3-fill" /></template>
