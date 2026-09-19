<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnrhh6btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnrhh6btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shopping-bag-alt" /></template>
