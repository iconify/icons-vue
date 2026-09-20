<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifxixjbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifxixjbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-broken" /></template>
