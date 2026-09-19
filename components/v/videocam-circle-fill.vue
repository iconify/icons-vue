<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibbrz397t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ibbrz397t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:videocam-circle-fill" /></template>
