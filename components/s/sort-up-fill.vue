<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae3m4ibfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae3m4ibfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-up-fill" /></template>
