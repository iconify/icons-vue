<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_fj8pw5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_fj8pw5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-kerning" /></template>
