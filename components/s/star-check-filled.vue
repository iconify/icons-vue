<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqd7f1bqb.css';
import '../../css/e/eatsjcb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqd7f1bqb"/><path class="eatsjcb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-check-filled" /></template>
