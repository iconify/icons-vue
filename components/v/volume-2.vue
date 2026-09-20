<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_n7oxbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_n7oxbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:volume-2" /></template>
