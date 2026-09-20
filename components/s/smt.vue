<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7nf2wbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7nf2wbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:smt" /></template>
