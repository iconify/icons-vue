<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-m-0jh-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-m-0jh-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sort-alt" /></template>
