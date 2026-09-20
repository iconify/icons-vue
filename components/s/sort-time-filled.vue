<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgk_62bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgk_62bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-time-filled" /></template>
