<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebj33kbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebj33kbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:store-solid" /></template>
