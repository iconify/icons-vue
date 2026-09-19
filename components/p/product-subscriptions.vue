<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlw61rbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlw61rbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:product-subscriptions" /></template>
