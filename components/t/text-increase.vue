<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qukf4fb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qukf4fb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-increase" /></template>
