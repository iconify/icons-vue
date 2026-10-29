<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r29c29bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r29c29bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tv" /></template>
