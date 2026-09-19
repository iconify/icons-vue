<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_np0rlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="mj_np0rlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:video" /></template>
