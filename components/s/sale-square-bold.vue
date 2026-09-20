<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8yj-_bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8yj-_bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sale-square-bold" /></template>
