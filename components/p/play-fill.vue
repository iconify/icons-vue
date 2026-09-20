<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zofvscc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zofvscc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-fill" /></template>
