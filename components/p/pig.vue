<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eka-vc8wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eka-vc8wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pig" /></template>
