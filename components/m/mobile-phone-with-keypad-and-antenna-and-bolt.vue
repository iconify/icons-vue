<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7jvj_bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p7jvj_bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-keypad-and-antenna-and-bolt" /></template>
