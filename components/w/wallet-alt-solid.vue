<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z02-h_bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z02-h_bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wallet-alt-solid" /></template>
