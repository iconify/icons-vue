<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_kcb60rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i_kcb60rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-charging-solid" /></template>
