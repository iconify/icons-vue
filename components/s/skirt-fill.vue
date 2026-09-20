<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eac3h2rig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eac3h2rig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skirt-fill" /></template>
