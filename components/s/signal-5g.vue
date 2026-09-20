<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppj4wo0ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppj4wo0ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-5g" /></template>
