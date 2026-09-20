<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otp0p-b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otp0p-b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-x" /></template>
