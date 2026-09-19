<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl3j48bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl3j48bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user" /></template>
