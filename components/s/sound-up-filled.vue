<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agai12bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agai12bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-up-filled" /></template>
