<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l83413rhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l83413rhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:merge-up-alt" /></template>
