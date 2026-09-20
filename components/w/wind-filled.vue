<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh-h126fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh-h126fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wind-filled" /></template>
