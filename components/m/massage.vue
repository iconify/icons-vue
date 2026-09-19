<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm21awbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm21awbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:massage" /></template>
