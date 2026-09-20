<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9cjrrk0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y9cjrrk0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wallet-remix" /></template>
