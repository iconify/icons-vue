<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saex-v3gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="saex-v3gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:selection-pin-in-out" /></template>
