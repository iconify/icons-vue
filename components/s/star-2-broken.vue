<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2742lupv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2742lupv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-2-broken" /></template>
