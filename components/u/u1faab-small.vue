<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmjoq-bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hmjoq-bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1faab-small" /></template>
