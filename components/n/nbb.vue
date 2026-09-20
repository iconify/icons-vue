<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-rq9_bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-rq9_bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nbb" /></template>
