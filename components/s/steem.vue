<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovnmu6bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ovnmu6bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:steem" /></template>
