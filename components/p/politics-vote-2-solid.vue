<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1zciwbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c1zciwbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:politics-vote-2-solid" /></template>
