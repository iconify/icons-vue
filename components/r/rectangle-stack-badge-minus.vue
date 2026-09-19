<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9rnavb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g9rnavb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-badge-minus" /></template>
