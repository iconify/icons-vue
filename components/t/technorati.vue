<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m17jfv7jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":480};
const content = `<path class="m17jfv7jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:technorati" /></template>
