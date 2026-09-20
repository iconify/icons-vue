<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3-sldb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3-sldb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-35-small" /></template>
