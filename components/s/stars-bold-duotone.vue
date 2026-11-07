<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4ekznb-a.css';
import '../../css/u/ucfqbabvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ekznb-a"/><path class="ucfqbabvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-bold-duotone" /></template>
