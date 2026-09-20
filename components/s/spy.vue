<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okjqmb5jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okjqmb5jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spy" /></template>
