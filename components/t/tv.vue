<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luejjmb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="luejjmb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tv" /></template>
