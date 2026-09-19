<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c405ufbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c405ufbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:spinner-two-alt" /></template>
