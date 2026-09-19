<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxppgib-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="dxppgib-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ssh" /></template>
