<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgig6s6kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgig6s6kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-half-sharp-fill" /></template>
