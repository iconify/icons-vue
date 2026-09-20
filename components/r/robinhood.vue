<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok2vuvm6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ok2vuvm6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:robinhood" /></template>
