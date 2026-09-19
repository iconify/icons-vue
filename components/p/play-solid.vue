<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb9e1ot7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb9e1ot7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:play-solid" /></template>
