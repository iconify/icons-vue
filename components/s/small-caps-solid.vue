<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-py-4wxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m-py-4wxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:small-caps-solid" /></template>
