<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0kylmbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="v0kylmbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-nurse" /></template>
