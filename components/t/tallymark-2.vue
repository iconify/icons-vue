<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi49o-bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi49o-bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tallymark-2" /></template>
