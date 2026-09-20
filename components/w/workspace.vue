<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fybd5wb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fybd5wb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:workspace" /></template>
