<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0rm51fwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v0rm51fwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:printer" /></template>
