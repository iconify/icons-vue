<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2e6bqb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2e6bqb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vaccine-bottle" /></template>
