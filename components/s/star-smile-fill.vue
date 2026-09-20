<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_n5rqe1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_n5rqe1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-smile-fill" /></template>
