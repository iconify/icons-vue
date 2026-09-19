<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py4dkfvij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py4dkfvij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:share" /></template>
