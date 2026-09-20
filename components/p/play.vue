<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3qp6x1gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qp6x1gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play" /></template>
