<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivvrc5b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivvrc5b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:product-hunt" /></template>
