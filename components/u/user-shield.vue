<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1csceyno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="a1csceyno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-shield" /></template>
