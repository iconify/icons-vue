<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br11ttb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br11ttb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:pentagon" /></template>
