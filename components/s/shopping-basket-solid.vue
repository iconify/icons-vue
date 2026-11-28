<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfsvxz4qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfsvxz4qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shopping-basket-solid" /></template>
