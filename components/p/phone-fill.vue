<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm2j-x-gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mm2j-x-gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-fill" /></template>
