<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7rc0abjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7rc0abjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:unpin-line" /></template>
