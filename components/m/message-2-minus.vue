<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x08w35tyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x08w35tyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-minus" /></template>
