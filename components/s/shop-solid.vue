<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixeh-hb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixeh-hb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:shop-solid" /></template>
