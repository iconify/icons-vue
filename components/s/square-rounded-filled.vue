<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1wpnu13c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1wpnu13c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-filled" /></template>
