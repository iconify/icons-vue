<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr7qnfbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr7qnfbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:revealdotjs" /></template>
