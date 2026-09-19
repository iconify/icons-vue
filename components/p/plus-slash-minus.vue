<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn2oaccna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wn2oaccna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-slash-minus" /></template>
