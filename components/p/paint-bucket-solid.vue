<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itgze75et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="itgze75et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paint-bucket-solid" /></template>
