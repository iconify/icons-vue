<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rki2gpn-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rki2gpn-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:test-tube-solid" /></template>
