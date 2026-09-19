<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqizaybtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqizaybtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paragraph-filled" /></template>
