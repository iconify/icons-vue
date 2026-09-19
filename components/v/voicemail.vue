<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz9y9syrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gz9y9syrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:voicemail" /></template>
