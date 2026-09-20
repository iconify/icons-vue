<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7fvrzbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7fvrzbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polygon-filled" /></template>
