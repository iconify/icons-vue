<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5t73gbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5t73gbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:writing-off" /></template>
