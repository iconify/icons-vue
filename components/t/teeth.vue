<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytycylhqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ytycylhqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:teeth" /></template>
