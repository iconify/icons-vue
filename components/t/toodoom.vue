<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io412tbjd.css';
import '../../css/o/oj-_-5bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="io412tbjd"/><path class="oj-_-5bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:toodoom" /></template>
