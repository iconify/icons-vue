<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nazi3gbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nazi3gbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:status" /></template>
