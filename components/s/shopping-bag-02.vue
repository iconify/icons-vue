<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6u8l-oou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6u8l-oou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:shopping-bag-02" /></template>
