<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlxc--bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hlxc--bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wolf-head-and-question-mark" /></template>
