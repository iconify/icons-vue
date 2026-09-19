<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2g91qadi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x2g91qadi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-4" /></template>
