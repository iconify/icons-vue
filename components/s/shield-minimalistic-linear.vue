<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isuqlx49y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isuqlx49y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-linear" /></template>
