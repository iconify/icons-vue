<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxx7ztbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxx7ztbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tags" /></template>
