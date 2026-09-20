<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucil41bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucil41bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-x" /></template>
