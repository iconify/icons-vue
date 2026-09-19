<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvdnofbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvdnofbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:viewfinder-dot-solid" /></template>
