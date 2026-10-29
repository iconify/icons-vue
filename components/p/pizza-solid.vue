<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1tyjpr-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1tyjpr-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pizza-solid" /></template>
