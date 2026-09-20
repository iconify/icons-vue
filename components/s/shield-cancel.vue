<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2nkf-gjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2nkf-gjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-cancel" /></template>
