<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5ljfv5ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ljfv5ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:packer" /></template>
