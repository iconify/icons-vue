<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl0xw-snl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="bl0xw-snl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:store" /></template>
