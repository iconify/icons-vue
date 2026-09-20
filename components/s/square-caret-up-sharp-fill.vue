<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d57v2tw1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d57v2tw1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-up-sharp-fill" /></template>
