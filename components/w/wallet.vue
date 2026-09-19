<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khlp6_3uj.css';
import '../../css/j/jr0jy1wli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khlp6_3uj"/><circle class="jr0jy1wli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:wallet" /></template>
