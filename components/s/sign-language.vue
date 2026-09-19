<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq6xfub6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq6xfub6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:sign-language" /></template>
