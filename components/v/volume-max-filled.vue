<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6q2q6bbg.css';
import '../../css/u/ut_zgf51k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6q2q6bbg"/><path class="ut_zgf51k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:volume-max-filled" /></template>
