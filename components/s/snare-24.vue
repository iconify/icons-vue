<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbq2xpfpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbq2xpfpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:snare-24" /></template>
