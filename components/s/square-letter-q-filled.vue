<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwk3xhbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwk3xhbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-q-filled" /></template>
