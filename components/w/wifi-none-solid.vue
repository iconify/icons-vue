<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq85p23jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qq85p23jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wifi-none-solid" /></template>
