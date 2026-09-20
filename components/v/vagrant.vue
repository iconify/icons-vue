<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2kdx0bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2kdx0bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vagrant" /></template>
