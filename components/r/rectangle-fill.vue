<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lya76wdsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lya76wdsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-fill" /></template>
