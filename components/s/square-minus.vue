<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvzl2lb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzl2lb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-minus" /></template>
