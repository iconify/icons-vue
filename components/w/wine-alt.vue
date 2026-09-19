<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owd41sbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owd41sbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wine-alt" /></template>
