<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk6_zlb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk6_zlb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-2-filled" /></template>
