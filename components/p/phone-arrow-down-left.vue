<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_hfiljnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o_hfiljnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-arrow-down-left" /></template>
