<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5sa4cbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5sa4cbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-underline-wave" /></template>
