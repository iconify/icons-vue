<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfhs4vv5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lfhs4vv5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pause-circle-fill" /></template>
