<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcoy1k6ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pcoy1k6ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:unlock-plant-filled" /></template>
