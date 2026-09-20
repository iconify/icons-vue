<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c85tht78u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c85tht78u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-cog" /></template>
