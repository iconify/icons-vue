<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwqzobcjb.css';
import '../../css/i/ildxxvqdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwqzobcjb"/><path class="ildxxvqdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-minimalistic-bold" /></template>
