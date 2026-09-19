<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4-7y7bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4-7y7bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shopping-bag-fill" /></template>
