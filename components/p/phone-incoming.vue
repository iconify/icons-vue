<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1madqn3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1madqn3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:phone-incoming" /></template>
