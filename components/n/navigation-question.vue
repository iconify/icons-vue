<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvlq6xbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvlq6xbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-question" /></template>
