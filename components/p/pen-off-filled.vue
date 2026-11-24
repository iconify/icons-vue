<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42fv8bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k42fv8bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pen-off-filled" /></template>
