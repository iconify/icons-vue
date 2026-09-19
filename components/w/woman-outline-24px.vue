<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e27kuvvqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e27kuvvqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:woman-outline-24px" /></template>
