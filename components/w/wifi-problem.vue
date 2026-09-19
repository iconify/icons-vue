<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofj4p7beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofj4p7beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:wifi-problem" /></template>
