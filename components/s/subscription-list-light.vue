<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kawm64b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kawm64b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:subscription-list-light" /></template>
