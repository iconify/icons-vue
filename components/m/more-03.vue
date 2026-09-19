<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_jvs0buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_jvs0buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-03" /></template>
