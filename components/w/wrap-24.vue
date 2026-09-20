<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n664vvbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n664vvbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:wrap-24" /></template>
