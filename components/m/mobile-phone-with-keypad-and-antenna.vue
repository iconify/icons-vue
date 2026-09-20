<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/govgh1bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="govgh1bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-keypad-and-antenna" /></template>
