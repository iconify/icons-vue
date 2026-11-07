<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvrwd2b_b.css';
import '../../css/f/f-cbj-b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvrwd2b_b"/><path class="f-cbj-b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-2-bold" /></template>
