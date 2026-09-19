<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3dl_ybuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u3dl_ybuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:personalhotspot" /></template>
