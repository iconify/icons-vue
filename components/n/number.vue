<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp7ixobut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fp7ixobut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:number" /></template>
