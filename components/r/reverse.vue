<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwt96rbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="bwt96rbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:reverse" /></template>
