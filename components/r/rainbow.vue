<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq5o2cbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq5o2cbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rainbow" /></template>
