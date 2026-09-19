<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9nwd2b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9nwd2b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-minus-solid" /></template>
