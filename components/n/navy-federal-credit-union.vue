<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o42jkxb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o42jkxb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:navy-federal-credit-union" /></template>
