<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl1s60bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl1s60bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:plus-outline" /></template>
