<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8uz9rbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c8uz9rbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pharmacy-solid" /></template>
