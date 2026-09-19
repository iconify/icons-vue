<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9s6xib5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9s6xib5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:speaker" /></template>
