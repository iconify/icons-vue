<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwx2ffbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="qwx2ffbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-jewish-11" /></template>
