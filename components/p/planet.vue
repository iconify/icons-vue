<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2nt36b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2nt36b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:planet" /></template>
