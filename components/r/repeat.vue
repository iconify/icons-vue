<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld1h7vbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld1h7vbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:repeat" /></template>
