<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jumlimbfi.css';
import '../../css/j/jcs69s1gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jumlimbfi"/><path clip-rule="evenodd" class="jcs69s1gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-laugh-solid" /></template>
