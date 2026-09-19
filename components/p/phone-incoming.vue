<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb7acdtln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb7acdtln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-incoming" /></template>
