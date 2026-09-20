<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5z3k_bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5z3k_bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sun-off" /></template>
