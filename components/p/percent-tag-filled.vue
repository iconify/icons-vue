<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niv9iacmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niv9iacmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:percent-tag-filled" /></template>
