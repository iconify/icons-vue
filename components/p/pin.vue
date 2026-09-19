<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azllpjbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azllpjbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pin" /></template>
