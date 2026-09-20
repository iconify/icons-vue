<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq52vybza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq52vybza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-mail-dark" /></template>
