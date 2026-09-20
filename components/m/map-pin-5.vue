<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7b_bhb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="x7b_bhb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:map-pin-5" /></template>
