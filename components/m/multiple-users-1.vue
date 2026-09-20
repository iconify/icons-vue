<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj1zm9bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj1zm9bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-users-1" /></template>
