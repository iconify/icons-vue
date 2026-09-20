<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdvz_fe7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdvz_fe7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:stove-induction-pot" /></template>
