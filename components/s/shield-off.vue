<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-6k-cc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6k-cc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shield-off" /></template>
