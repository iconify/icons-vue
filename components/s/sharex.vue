<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvimmnbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvimmnbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sharex" /></template>
