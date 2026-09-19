<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b487_1s0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b487_1s0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pencil-slash" /></template>
