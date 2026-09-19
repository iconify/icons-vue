<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ambom8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ambom8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-minus" /></template>
