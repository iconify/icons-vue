<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4uqso-ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4uqso-ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wash-dry-flat" /></template>
